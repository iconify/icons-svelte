<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox-4if7um.css';
import '../../css/l/ld9a8ebwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ox-4if7um"/><path class="ld9a8ebwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ski-lift-20" {...props}></Icon>
