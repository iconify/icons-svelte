<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyvhupqky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyvhupqky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:vertical-align-bottom" {...props}></Icon>
