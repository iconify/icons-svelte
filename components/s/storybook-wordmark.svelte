<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4sclebpp.css';
import '../../css/o/o1kac1bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="o4sclebpp"/><path class="o1kac1bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:storybook-wordmark" {...props}></Icon>
