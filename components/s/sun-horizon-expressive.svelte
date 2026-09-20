<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buiy88btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="buiy88btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:sun-horizon-expressive" {...props}></Icon>
