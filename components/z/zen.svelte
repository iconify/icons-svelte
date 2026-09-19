<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emfql_bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emfql_bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:zen" {...props}></Icon>
