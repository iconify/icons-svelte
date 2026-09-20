<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mybqkzbci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mybqkzbci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sagemath" {...props}></Icon>
