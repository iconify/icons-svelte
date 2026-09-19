<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj4k0mbbu.css';
import '../../css/m/mpad8yq0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":470};
const content = `<path class="fj4k0mbbu"/><path class="mpad8yq0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:thumbsdown" {...props}></Icon>
