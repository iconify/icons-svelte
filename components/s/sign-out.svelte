<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq0ae0b0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bq0ae0b0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:sign-out" {...props}></Icon>
