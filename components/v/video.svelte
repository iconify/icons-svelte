<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eeq14dbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eeq14dbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:video" {...props}></Icon>
