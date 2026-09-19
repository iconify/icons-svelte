<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/f/f42gr3bqh.css';
import '../../css/n/n63w7jmfp.css';
import '../../css/b/bq8_86bhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f42gr3bqh"/><path class="n63w7jmfp"/><path class="bq8_86bhz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:time-zone" {...props}></Icon>
