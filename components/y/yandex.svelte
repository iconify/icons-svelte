<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp9i4h5xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lp9i4h5xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:yandex" {...props}></Icon>
