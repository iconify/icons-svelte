<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg7ewom7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="tg7ewom7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:xls-solid" {...props}></Icon>
