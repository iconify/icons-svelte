<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_b-gubjy.css';
import '../../css/m/m8pf_nbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x_b-gubjy"/><path class="m8pf_nbon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:switch-button" {...props}></Icon>
