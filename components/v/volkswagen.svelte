<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1wzkiiij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1wzkiiij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:volkswagen" {...props}></Icon>
