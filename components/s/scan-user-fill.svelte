<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz27u516v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tz27u516v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:scan-user-fill" {...props}></Icon>
