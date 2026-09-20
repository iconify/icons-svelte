<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um-rl65_a.css';
import '../../css/t/tri62lhrx.css';
import '../../css/b/bqonxyhrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um-rl65_a"/><path class="tri62lhrx"/><path class="bqonxyhrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:time" {...props}></Icon>
