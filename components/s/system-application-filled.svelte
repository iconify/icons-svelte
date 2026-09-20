<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz_r39ypr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hz_r39ypr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:system-application-filled" {...props}></Icon>
