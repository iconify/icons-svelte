<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydk_n5baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ydk_n5baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:trx" {...props}></Icon>
