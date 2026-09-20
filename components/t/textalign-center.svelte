<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttyx4f7fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttyx4f7fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:textalign-center" {...props}></Icon>
