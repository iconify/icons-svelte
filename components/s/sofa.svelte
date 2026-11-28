<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc3et9b2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc3et9b2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:sofa" {...props}></Icon>
