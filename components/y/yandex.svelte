<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_v1athia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f_v1athia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:yandex" {...props}></Icon>
