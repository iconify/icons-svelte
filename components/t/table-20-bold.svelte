<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i48le1b7u.css';
import '../../css/w/wx0wzhb6i.css';
import '../../css/a/amp8719fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i48le1b7u"/><path class="wx0wzhb6i"/><path class="amp8719fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:table-20-bold" {...props}></Icon>
