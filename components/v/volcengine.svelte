<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz7x-rb-m.css';
import '../../css/q/qk8x-bb5p.css';
import '../../css/a/akdxg9upc.css';
import '../../css/m/mz595l-ia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oz7x-rb-m"/><path class="qk8x-bb5p"/><path class="akdxg9upc"/><path class="mz595l-ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:volcengine" {...props}></Icon>
