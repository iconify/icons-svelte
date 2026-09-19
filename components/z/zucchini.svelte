<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcfai4b-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcfai4b-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:zucchini" {...props}></Icon>
