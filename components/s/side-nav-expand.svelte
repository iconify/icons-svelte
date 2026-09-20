<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nskmalzgz.css';
import '../../css/k/khw_e2oxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nskmalzgz"/><path class="khw_e2oxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:side-nav-expand" {...props}></Icon>
