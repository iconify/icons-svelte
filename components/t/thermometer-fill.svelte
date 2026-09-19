<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mirf0bblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mirf0bblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:thermometer-fill" {...props}></Icon>
