<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr3kfjbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr3kfjbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:washing-machine" {...props}></Icon>
