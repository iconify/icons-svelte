<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqc3k61jp.css';
import '../../css/z/z4lv28bay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqc3k61jp"/><path class="z4lv28bay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:trash" {...props}></Icon>
