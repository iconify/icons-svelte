<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti7oq7bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ti7oq7bew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:scissors" {...props}></Icon>
