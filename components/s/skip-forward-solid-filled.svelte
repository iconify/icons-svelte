<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-zstca3u.css';
import '../../css/q/qivzlzbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d-zstca3u"/><path class="qivzlzbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:skip-forward-solid-filled" {...props}></Icon>
