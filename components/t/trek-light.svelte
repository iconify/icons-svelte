<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-65cw99i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a-65cw99i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trek-light" {...props}></Icon>
