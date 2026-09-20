<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1qq4suqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1qq4suqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:slate-edit" {...props}></Icon>
