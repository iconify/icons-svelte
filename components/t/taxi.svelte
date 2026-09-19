<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-k1b_1rw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q-k1b_1rw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:taxi" {...props}></Icon>
