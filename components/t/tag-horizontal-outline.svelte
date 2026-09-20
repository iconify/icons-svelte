<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9zi6020g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t9zi6020g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tag-horizontal-outline" {...props}></Icon>
