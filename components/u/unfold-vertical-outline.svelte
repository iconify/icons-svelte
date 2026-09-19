<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4egcmb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path clip-rule="evenodd" class="m4egcmb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:unfold-vertical-outline" {...props}></Icon>
