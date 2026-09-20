<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg8ef5bno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zg8ef5bno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:text-align-center-solid" {...props}></Icon>
