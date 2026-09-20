<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhb4zd4zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="mhb4zd4zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:squarespace" {...props}></Icon>
