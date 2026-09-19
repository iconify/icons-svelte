<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqrtldgzg.css';
import '../../css/p/p5kyztbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="gqrtldgzg"/><path class="p5kyztbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:tensorflow-wordmark" {...props}></Icon>
