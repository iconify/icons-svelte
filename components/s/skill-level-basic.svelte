<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6-_lr_vw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l6-_lr_vw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:skill-level-basic" {...props}></Icon>
