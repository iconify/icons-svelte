<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve1tpjbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ve1tpjbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yandex-dark" {...props}></Icon>
