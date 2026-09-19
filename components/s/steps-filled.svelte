<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_wfe124o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_wfe124o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:steps-filled" {...props}></Icon>
