<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk-idjbly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":580.641,"height":1000};
const content = `<path class="lk-idjbly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:yandex" {...props}></Icon>
