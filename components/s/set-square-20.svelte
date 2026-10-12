<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqcluhbqi.css';
import '../../css/q/qn6jbqb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fqcluhbqi"/><path class="qn6jbqb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:set-square-20" {...props}></Icon>
