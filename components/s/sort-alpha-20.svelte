<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxmhc0blm.css';
import '../../css/e/eirizwgnj.css';
import '../../css/q/qck7pccit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uxmhc0blm"/><path class="eirizwgnj"/><path class="qck7pccit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sort-alpha-20" {...props}></Icon>
