<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzdt1ttbh.css';
import '../../css/i/i54cwlb3q.css';
import '../../css/p/p0o3chmxj.css';
import '../../css/n/n2nb_4gbg.css';
import '../../css/t/tsspwqbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jzdt1ttbh"/><path class="i54cwlb3q"/><path class="p0o3chmxj"/><path class="n2nb_4gbg"/><path class="tsspwqbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:yii-wordmark" {...props}></Icon>
