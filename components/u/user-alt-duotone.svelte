<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf1wx9bka.css';
import '../../css/r/r29erebio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="pf1wx9bka"/><path class="r29erebio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:user-alt-duotone" {...props}></Icon>
