<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/on6yy0byj.css';
import '../../css/m/md286fbip.css';
import '../../css/f/fe4paj2jh.css';
import '../../css/b/bt3k7sqta.css';
import '../../css/u/unmcvlw0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="on6yy0byj"/><g class="md286fbip"><path class="fe4paj2jh"/><path class="bt3k7sqta"/><path class="unmcvlw0v"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:zen" {...props}></Icon>
