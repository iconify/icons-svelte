<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak6hi0bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ak6hi0bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-x-fill" {...props}></Icon>
