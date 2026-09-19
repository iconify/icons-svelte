<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttw5pwbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":666};
const content = `<path class="ttw5pwbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:shopping" {...props}></Icon>
