<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kk1hzjbgp.css';
import '../../css/m/md286fbip.css';
import '../../css/j/jzowogbqz.css';
import '../../css/w/wsyxhjaet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="kk1hzjbgp"/><g class="md286fbip"><path class="jzowogbqz"/><path class="wsyxhjaet"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:sin" {...props}></Icon>
