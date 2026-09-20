<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3os1xhir.css';
import '../../css/w/wjlktkbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3os1xhir"/><path class="wjlktkbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:temperature-thermometer-medium-bold" {...props}></Icon>
