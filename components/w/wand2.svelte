<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6v3-8bhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k6v3-8bhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wand2" {...props}></Icon>
