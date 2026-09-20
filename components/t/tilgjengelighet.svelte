<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeyw3hn-y.css';
import '../../css/f/fdorp31hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aeyw3hn-y"/><path class="fdorp31hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:tilgjengelighet" {...props}></Icon>
