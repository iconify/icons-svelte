<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6hk6n6ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u6hk6n6ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:vacuum2" {...props}></Icon>
