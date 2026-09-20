<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6jgc5b_g.css';
import '../../css/h/hllvxmbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f6jgc5b_g"/><path class="hllvxmbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:settings-thick-duotone" {...props}></Icon>
