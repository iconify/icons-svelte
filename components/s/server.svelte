<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jyh615bzz.css';
import '../../css/n/n4acc3bci.css';
import '../../css/m/mx6yo8buj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jyh615bzz"/><rect class="n4acc3bci"/><path class="mx6yo8buj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:server" {...props}></Icon>
