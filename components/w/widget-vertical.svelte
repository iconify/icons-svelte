<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv7lhtbjv.css';
import '../../css/b/bou7a7jit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mv7lhtbjv"/><path class="bou7a7jit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:widget-vertical" {...props}></Icon>
