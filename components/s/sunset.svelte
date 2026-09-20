<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou-rhibbk.css';
import '../../css/v/vlj0scbpf.css';
import '../../css/d/d-2gb0bhq.css';
import '../../css/h/hq2lhabny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<defs><clipPath id="SVGzpDhEbnf"><path class="ou-rhibbk"/></clipPath><symbol id="SVGYqAb8ZRw" viewBox="0 0 375 375"><circle class="vlj0scbpf"/><path class="d-2gb0bhq"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="rotate" values="0 187.5 187.5; 45 187.5 187.5"/></path></symbol></defs><g clip-path="url(#SVGzpDhEbnf)"><use width="375" height="375" href="#SVGYqAb8ZRw" transform="translate(68.5 104.5)"/></g><path class="hq2lhabny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteocons:sunset" {...props}></Icon>
