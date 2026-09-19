<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izpv9_ypd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izpv9_ypd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:sidebar" {...props}></Icon>
