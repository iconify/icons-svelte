<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb2yg1baz.css';
import '../../css/q/qzo006suv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<circle class="nb2yg1baz"/><path class="qzo006suv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:sun-fill-12" {...props}></Icon>
