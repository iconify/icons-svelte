<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecxavkbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":840,"height":790};
const content = `<path class="ecxavkbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:youtube" {...props}></Icon>
