<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl9k6ubdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl9k6ubdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:talend" {...props}></Icon>
