<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_r4qxznw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p_r4qxznw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tag-outline" {...props}></Icon>
