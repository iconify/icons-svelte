<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz1pcacve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pz1pcacve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:tea-cup" {...props}></Icon>
