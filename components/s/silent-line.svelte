<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmizg-b1r.css';
import '../../css/n/nu2y03fco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmizg-b1r"/><path class="nu2y03fco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:silent-line" {...props}></Icon>
