<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqank8f6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hqank8f6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:smart-speaker" {...props}></Icon>
