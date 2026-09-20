<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk8un56ea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fk8un56ea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:target-3-remix" {...props}></Icon>
