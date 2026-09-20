<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjxc99b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mjxc99b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:satt" {...props}></Icon>
