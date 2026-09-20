<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqtutlw0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqtutlw0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:zbc" {...props}></Icon>
