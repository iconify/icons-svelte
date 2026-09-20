<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq1db9bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oq1db9bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:zircuit" {...props}></Icon>
