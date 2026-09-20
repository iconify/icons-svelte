<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b2nzvx1us.css';
import '../../css/s/s_plwmgtd.css';
import '../../css/q/qzzhnccem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b2nzvx1us"/><path class="s_plwmgtd"/><path class="qzzhnccem"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:view-binocular" {...props}></Icon>
