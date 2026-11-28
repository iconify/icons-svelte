<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd52webnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd52webnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ski-solid" {...props}></Icon>
