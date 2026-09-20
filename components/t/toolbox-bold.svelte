<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i18y50gyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i18y50gyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:toolbox-bold" {...props}></Icon>
