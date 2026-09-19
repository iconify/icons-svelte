<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a6yqdssfg.css';
import '../../css/k/kyfg5ffjz.css';
import '../../css/c/ch-h2szyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a6yqdssfg"/><path class="kyfg5ffjz"/><path class="ch-h2szyi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:shopping-card-remove-thin" {...props}></Icon>
