<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qfvuet28o.css';
import '../../css/g/g452hhy9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qfvuet28o"/><path class="g452hhy9a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:wallet-duotone" {...props}></Icon>
