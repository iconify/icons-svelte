<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1wh0vbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1wh0vbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:virtualbox" {...props}></Icon>
