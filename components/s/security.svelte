<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rulstbbgo.css';
import '../../css/c/c3te-ab8q.css';
import '../../css/x/x35msp2lf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rulstbbgo"/><path class="c3te-ab8q"/><path class="x35msp2lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:security" {...props}></Icon>
