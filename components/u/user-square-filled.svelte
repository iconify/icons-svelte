<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmdrs99jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nmdrs99jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:user-square-filled" {...props}></Icon>
