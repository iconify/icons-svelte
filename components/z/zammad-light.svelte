<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu3q8dilk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eu3q8dilk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zammad-light" {...props}></Icon>
