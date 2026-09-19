<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq_ak0bad.css';
import '../../css/v/v03ymlbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hq_ak0bad"/><path class="v03ymlbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:trash" {...props}></Icon>
