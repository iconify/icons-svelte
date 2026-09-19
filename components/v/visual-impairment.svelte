<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpo8tnbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpo8tnbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:visual-impairment" {...props}></Icon>
