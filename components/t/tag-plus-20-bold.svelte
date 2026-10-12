<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-n28l9jj.css';
import '../../css/m/ml0uh1b4e.css';
import '../../css/x/xwdhawfba.css';
import '../../css/h/hayl1lfmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o-n28l9jj"/><path class="ml0uh1b4e"/><path class="xwdhawfba"/><path class="hayl1lfmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tag-plus-20-bold" {...props}></Icon>
