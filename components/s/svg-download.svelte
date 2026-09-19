<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k21sdcbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k21sdcbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:svg-download" {...props}></Icon>
