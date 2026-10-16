<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opadiwbki.css';
import '../../css/y/yk_ojccds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="opadiwbki"/><path class="yk_ojccds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:subscript-20" {...props}></Icon>
