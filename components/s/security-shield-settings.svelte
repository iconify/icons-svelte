<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/n/nc1ozk_pl.css';
import '../../css/g/glgyo9tzv.css';
import '../../css/m/mbub22b_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="nc1ozk_pl"/><path class="glgyo9tzv"/><path class="mbub22b_g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:security-shield-settings" {...props}></Icon>
