<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eccpoibnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":32};
const content = `<path class="eccpoibnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:shield" {...props}></Icon>
