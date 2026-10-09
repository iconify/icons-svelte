<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1middb0q.css';
import '../../css/b/b_86fhc7i.css';
import '../../css/n/nwv555bhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l1middb0q"/><path class="b_86fhc7i"/><path class="nwv555bhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:washing-machine-20" {...props}></Icon>
