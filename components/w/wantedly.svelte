<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca0t0rb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ca0t0rb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:wantedly" {...props}></Icon>
