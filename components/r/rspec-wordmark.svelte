<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyy9a3gfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vyy9a3gfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:rspec-wordmark" {...props}></Icon>
