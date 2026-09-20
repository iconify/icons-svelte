<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k60p3tbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k60p3tbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:statecloud" {...props}></Icon>
