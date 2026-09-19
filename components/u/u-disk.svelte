<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/f/f9ebc66zp.css';
import '../../css/u/uc6h75bkl.css';
import '../../css/h/hvb9uqbww.css';
import '../../css/k/k_4c4kb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="f9ebc66zp"/><path class="uc6h75bkl"/><path class="hvb9uqbww"/><path class="k_4c4kb-q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:u-disk" {...props}></Icon>
