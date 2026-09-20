<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdrq5fk-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hdrq5fk-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tennis" {...props}></Icon>
