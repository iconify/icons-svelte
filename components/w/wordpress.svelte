<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilndq7y4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="ilndq7y4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:wordpress" {...props}></Icon>
