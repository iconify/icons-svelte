<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs6krb0lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vs6krb0lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:zoom-in-line" {...props}></Icon>
