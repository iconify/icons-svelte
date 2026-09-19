<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtnqr6iwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wtnqr6iwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:xmy" {...props}></Icon>
