<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1mjunbsu.css';
import '../../css/a/a9x7u0jlb.css';
import '../../css/d/deeciebvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVG8ATWfIoq" class="n1mjunbsu"><path class="a9x7u0jlb"/></mask><path mask="url(#SVG8ATWfIoq)" class="deeciebvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:windows-solid" {...props}></Icon>
