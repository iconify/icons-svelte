<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psxx8-rbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psxx8-rbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shield-filled" {...props}></Icon>
