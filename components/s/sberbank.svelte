<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxm51gybk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fxm51gybk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:sberbank" {...props}></Icon>
