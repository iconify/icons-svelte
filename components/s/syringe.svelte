<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y09gvdb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y09gvdb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:syringe" {...props}></Icon>
