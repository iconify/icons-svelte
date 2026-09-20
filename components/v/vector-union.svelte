<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch6n-rbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ch6n-rbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:vector-union" {...props}></Icon>
