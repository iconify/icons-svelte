<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i38todi1o.css';
import '../../css/x/xv802vxka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i38todi1o"/><path class="xv802vxka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:table-delete" {...props}></Icon>
