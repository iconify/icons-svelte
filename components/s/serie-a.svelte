<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okmv9tbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okmv9tbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:serie-a" {...props}></Icon>
