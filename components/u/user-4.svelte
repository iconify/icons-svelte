<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae0kc3blq.css';
import '../../css/r/r8w6x7bjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="ae0kc3blq"/><path class="r8w6x7bjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:user-4" {...props}></Icon>
