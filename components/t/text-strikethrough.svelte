<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atkvy_bhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="atkvy_bhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-strikethrough" {...props}></Icon>
