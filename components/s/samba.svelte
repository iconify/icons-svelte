<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofd9gvb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofd9gvb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:samba" {...props}></Icon>
