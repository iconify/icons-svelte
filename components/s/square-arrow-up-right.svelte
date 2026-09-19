<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jvtjbnueh.css';
import '../../css/p/phpsd8buj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jvtjbnueh"/><path class="phpsd8buj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:square-arrow-up-right" {...props}></Icon>
