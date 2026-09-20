<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/t/thfq4gbnm.css';
import '../../css/w/wd4pbac6a.css';
import '../../css/k/kubn6vbik.css';
import '../../css/y/ywpiuebfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="thfq4gbnm"/><path class="wd4pbac6a"/><path class="kubn6vbik"/><path class="ywpiuebfh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:sword" {...props}></Icon>
