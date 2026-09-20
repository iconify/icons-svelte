<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7aq6nb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o7aq6nb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:slash-square-filled" {...props}></Icon>
