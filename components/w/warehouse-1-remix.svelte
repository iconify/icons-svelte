<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/deguiybxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="deguiybxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:warehouse-1-remix" {...props}></Icon>
