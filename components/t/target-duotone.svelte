<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v5oqn8unq.css';
import '../../css/b/bb6-6oplo.css';
import '../../css/h/hex7kcqxe.css';
import '../../css/e/ehsr83pwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="v5oqn8unq"/><path class="bb6-6oplo"/><path class="hex7kcqxe"/><path class="ehsr83pwr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:target-duotone" {...props}></Icon>
